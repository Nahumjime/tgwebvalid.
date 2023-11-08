$initData = $bot->validateInitData('query_id=...');

if (!$initData) {
    // validation fails
}

/**
 * The initData object can contain the following data:
 */

// Time opening a web application
$initData->authDate;

// An object containing data about the current user
$initData->user;

// May contain a chat partner data object
$initData->receiver;

// May contain an object with chat data
$initData->chat;

// and other data
